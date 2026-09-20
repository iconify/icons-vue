<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeqa6dbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jeqa6dbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bit" /></template>
