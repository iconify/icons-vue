<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/seiiy8a5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="seiiy8a5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:harbor-11" /></template>
