<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_ufcgbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="d_ufcgbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:adobe-photoshop" /></template>
