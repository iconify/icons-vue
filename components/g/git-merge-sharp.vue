<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfif4pbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfif4pbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:git-merge-sharp" /></template>
