<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgbt92b6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jgbt92b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:album-outline" /></template>
