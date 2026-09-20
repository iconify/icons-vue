<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3tg8gb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d3tg8gb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:dna-flat" /></template>
