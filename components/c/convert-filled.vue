<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrdnb5auz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrdnb5auz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:convert-filled" /></template>
