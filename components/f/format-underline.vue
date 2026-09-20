<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1_pa_blx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1_pa_blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:format-underline" /></template>
