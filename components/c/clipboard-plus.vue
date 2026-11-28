<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs2-47bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs2-47bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clipboard-plus" /></template>
