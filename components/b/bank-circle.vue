<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h20n09zle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h20n09zle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bank-circle" /></template>
