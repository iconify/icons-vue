<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxp3c3b-j.css';
import '../../css/q/qg_wop5ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxp3c3b-j"/><path class="qg_wop5ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:grain" /></template>
