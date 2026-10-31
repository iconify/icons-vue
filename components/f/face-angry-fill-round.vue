<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1j18jb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1j18jb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-angry-fill-round" /></template>
