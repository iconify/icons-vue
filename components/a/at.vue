<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rom2-fbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rom2-fbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:at" /></template>
