<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpe39fbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpe39fbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:code-outline" /></template>
