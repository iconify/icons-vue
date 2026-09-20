<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgoe6vbte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgoe6vbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:genderless-fill" /></template>
