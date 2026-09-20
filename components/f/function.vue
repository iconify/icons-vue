<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm5vxgbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="qm5vxgbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:function" /></template>
