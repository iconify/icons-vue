<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foac4kbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="foac4kbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chart-square-filled" /></template>
