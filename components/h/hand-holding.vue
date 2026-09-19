<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8doegbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="r8doegbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-holding" /></template>
