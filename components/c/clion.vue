<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru5zq38hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru5zq38hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:clion" /></template>
