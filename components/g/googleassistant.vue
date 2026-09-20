<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9f4_gbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9f4_gbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:googleassistant" /></template>
