<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo3513bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="eo3513bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:american-sign-language-interpreting" /></template>
