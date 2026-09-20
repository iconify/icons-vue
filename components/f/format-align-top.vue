<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwe_2jbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwe_2jbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:format-align-top" /></template>
