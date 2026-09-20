<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt4x0ywtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt4x0ywtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bower" /></template>
