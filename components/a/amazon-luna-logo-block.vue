<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvo319btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hvo319btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:amazon-luna-logo-block" /></template>
