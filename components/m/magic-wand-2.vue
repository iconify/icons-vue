<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg0p46jjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg0p46jjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:magic-wand-2" /></template>
