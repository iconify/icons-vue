<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irli_mh2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="irli_mh2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:graduation-cap" /></template>
