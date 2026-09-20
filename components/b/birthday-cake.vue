<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtoo5n7pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gtoo5n7pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:birthday-cake" /></template>
