<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwv613bdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="xwv613bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:download-from-cloud" /></template>
