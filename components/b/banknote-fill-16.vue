<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2rg7xbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="c2rg7xbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:banknote-fill-16" /></template>
