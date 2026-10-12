<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d43t32b4m.css';
import '../../css/y/y6ixysbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d43t32b4m"/><path class="y6ixysbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:book-contacts-stroke-20" /></template>
