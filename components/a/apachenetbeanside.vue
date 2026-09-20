<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-6y6ibqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-6y6ibqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:apachenetbeanside" /></template>
