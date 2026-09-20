<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwwh6z39s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xwwh6z39s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:3g" /></template>
