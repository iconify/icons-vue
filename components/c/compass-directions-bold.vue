<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c62vqsb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c62vqsb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:compass-directions-bold" /></template>
