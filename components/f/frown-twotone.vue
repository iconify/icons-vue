<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv_brepse.css';
import '../../css/r/rkhkgmbuh.css';
import '../../css/r/r361ix1oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yv_brepse"/><path class="rkhkgmbuh"/><path class="r361ix1oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:frown-twotone" /></template>
