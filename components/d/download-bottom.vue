<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5trh4bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5trh4bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:download-bottom" /></template>
