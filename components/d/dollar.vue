<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x83zgdb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x83zgdb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:dollar" /></template>
