<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdddszbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdddszbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:download" /></template>
