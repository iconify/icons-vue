<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cstoc4c1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cstoc4c1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:brackets-solid" /></template>
