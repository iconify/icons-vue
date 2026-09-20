<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/koj92m8jb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="koj92m8jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hapi" /></template>
