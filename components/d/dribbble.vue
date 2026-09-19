<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l75s777xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l75s777xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:dribbble" /></template>
