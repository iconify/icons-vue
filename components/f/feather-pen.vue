<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgahaqbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgahaqbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:feather-pen" /></template>
