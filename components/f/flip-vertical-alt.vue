<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5_l9__yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h5_l9__yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:flip-vertical-alt" /></template>
