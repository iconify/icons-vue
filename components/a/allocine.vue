<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq71m7b9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq71m7b9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:allocine" /></template>
