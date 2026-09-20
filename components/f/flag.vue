<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy_mfkb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yy_mfkb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:flag" /></template>
