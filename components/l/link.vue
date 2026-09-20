<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtnwm7b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtnwm7b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:link" /></template>
