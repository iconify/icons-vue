<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efs0dg7sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="efs0dg7sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bookmark-x-filled" /></template>
