<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/digkmr3fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="digkmr3fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:file-medical" /></template>
