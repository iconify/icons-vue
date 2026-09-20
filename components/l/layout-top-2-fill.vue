<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6r3seouz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6r3seouz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-top-2-fill" /></template>
