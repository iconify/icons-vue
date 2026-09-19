<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfgpndd3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cfgpndd3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:hash" /></template>
