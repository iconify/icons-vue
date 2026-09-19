<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv_ln2l9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="yv_ln2l9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:fast-forward" /></template>
