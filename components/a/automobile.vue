<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym0pkgb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":896};
const content = `<path class="ym0pkgb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:automobile" /></template>
