<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqbvycczd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqbvycczd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:alert-triangle" /></template>
