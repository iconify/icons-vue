<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-tp38bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e-tp38bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:elipse-frame-solid" /></template>
