<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7luzgj2a.css';
import '../../css/x/x_dypm6zl.css';
import '../../css/z/zi3h6zbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i7luzgj2a"/><path class="x_dypm6zl"/><path class="zi3h6zbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cabin-20-bold" /></template>
