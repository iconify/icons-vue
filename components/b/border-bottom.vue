<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgpc9ugqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgpc9ugqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:border-bottom" /></template>
