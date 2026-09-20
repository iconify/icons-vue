<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7e8svs6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7e8svs6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-question" /></template>
