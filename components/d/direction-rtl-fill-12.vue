<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmt3q2buw.css';
import '../../css/q/qstrk3-9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zmt3q2buw"/><path class="qstrk3-9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:direction-rtl-fill-12" /></template>
