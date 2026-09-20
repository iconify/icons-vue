<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6wkj5prr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6wkj5prr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-square-up-filled" /></template>
