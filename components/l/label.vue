<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz40gqnrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jz40gqnrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:label" /></template>
