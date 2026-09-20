<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb7vipbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fb7vipbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:alt-a" /></template>
