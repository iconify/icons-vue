<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaz9mm0_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vaz9mm0_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:folder-question" /></template>
