<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n351nwb6r.css';
import '../../css/z/zw_v3acsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n351nwb6r"/><path class="zw_v3acsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:hospital-symbol" /></template>
