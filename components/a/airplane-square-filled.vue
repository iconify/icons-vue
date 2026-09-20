<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdz7jqbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdz7jqbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:airplane-square-filled" /></template>
