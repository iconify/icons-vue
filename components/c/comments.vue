<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yld8hwb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="yld8hwb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:comments" /></template>
