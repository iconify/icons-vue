<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3kwjhb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3kwjhb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:bars-sort" /></template>
