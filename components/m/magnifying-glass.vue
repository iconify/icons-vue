<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1j8od6ti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b1j8od6ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:magnifying-glass" /></template>
