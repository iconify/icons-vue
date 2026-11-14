<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed5_uy-8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed5_uy-8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-links" /></template>
