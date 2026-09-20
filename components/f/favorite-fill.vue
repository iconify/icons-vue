<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psjehab6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psjehab6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:favorite-fill" /></template>
