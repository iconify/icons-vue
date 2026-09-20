<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f40vwcb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f40vwcb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:border-bottom" /></template>
