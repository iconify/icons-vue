<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brdjebbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="brdjebbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:book-closed-fill-20" /></template>
