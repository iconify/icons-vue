<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxkizf0gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxkizf0gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:content-save-all" /></template>
