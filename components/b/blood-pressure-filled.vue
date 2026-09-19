<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyce6dy-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyce6dy-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:blood-pressure-filled" /></template>
