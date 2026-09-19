<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkkui7jtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gkkui7jtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:arrow-back-thick-fill" /></template>
