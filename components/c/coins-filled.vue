<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5aytr1du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g5aytr1du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:coins-filled" /></template>
