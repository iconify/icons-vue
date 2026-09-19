<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iot5qp33d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1792};
const content = `<path class="iot5qp33d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:highchair" /></template>
