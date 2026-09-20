<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyu1mvble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cyu1mvble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:forward-email-flat" /></template>
