<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5i68obbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w5i68obbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:list-x2-filled" /></template>
