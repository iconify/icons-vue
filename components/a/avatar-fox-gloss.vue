<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8j3v-iti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8j3v-iti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-fox-gloss" /></template>
