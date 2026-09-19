<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujzieab0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujzieab0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:color-fill-filled" /></template>
