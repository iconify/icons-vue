<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si1cdrbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si1cdrbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:aerial-lift-fill" /></template>
