<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf838kbvj.css';
import '../../css/h/hp757egpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zf838kbvj"/><path class="hp757egpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-straight-right-filled" /></template>
