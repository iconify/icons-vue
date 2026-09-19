<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnt7c7sej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1664};
const content = `<path class="rnt7c7sej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:kakaotalk" /></template>
