<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4wf4bc1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="t4wf4bc1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:braille" /></template>
