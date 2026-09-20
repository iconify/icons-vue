<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy1_gac9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dy1_gac9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:egnyte-logo-block" /></template>
