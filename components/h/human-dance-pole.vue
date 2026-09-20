<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jacv8ut1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jacv8ut1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-dance-pole" /></template>
