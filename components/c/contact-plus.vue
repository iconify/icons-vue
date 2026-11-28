<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it78czskb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it78czskb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:contact-plus" /></template>
