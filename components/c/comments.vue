<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhjprcbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1600};
const content = `<path class="dhjprcbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:comments" /></template>
