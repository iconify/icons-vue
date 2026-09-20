<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk9zmhbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk9zmhbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:discord" /></template>
