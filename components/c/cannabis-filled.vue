<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziweoj99g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ziweoj99g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cannabis-filled" /></template>
