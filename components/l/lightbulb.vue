<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crb8r2b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crb8r2b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:lightbulb" /></template>
