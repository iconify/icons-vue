<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7ex7-bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7ex7-bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:carlsberg-group" /></template>
