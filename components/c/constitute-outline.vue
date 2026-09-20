<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi53r86ip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gi53r86ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:constitute-outline" /></template>
