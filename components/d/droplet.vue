<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as-y2cceh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="as-y2cceh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:droplet" /></template>
