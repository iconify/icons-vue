<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh1am04is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="rh1am04is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:invision" /></template>
