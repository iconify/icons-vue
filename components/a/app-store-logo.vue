<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbehteb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbehteb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:app-store-logo" /></template>
