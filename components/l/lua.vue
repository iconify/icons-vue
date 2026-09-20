<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pixerbbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pixerbbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:lua" /></template>
