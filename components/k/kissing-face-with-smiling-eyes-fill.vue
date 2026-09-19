<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5hnrcbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x5hnrcbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:kissing-face-with-smiling-eyes-fill" /></template>
