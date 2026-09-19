<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgmhlbdrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pgmhlbdrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-bar-square-plus-filled" /></template>
