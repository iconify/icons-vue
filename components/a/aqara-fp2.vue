<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwke2fiie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwke2fiie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-fp2" /></template>
