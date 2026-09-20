<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm_2psbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cm_2psbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:japanese-teacup" /></template>
