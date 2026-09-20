<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-tvso-gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-tvso-gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kirby" /></template>
