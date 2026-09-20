<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmexoo1yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmexoo1yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:close-square-filled" /></template>
