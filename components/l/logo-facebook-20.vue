<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po9ungb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="po9ungb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:logo-facebook-20" /></template>
