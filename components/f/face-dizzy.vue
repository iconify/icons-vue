<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww4fyqbuj.css';
import '../../css/w/wy7ugsoed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ww4fyqbuj"/><path class="wy7ugsoed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:face-dizzy" /></template>
