<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj3qrn2fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj3qrn2fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate-color:like" /></template>
