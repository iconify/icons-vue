<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjb3j2bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjb3j2bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:alwaysdata" /></template>
