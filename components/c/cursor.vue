<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibpc1qyqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibpc1qyqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:cursor" /></template>
