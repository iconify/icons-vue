<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv20ivdet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv20ivdet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cart-alt-2" /></template>
