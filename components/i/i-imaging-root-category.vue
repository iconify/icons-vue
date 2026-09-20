<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aml4e2bhz.css';
import '../../css/o/oge-yxbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="aml4e2bhz"/><path class="oge-yxbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-imaging-root-category" /></template>
