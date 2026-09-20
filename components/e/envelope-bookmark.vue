<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux8hyabok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux8hyabok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:envelope-bookmark" /></template>
