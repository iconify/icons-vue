<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex4r1ebmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ex4r1ebmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:directions-sign" /></template>
