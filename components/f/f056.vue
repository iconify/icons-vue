<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2-zhbbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="n2-zhbbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:f056" /></template>
