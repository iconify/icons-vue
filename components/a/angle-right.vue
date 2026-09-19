<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex-j_h13o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="ex-j_h13o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:angle-right" /></template>
