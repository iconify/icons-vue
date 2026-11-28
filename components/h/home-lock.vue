<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjcrk6n9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjcrk6n9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:home-lock" /></template>
