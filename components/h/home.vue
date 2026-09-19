<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muq5rlovc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":748,"height":680};
const content = `<path class="muq5rlovc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:home" /></template>
