<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8pqhd-yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8pqhd-yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:droplet" /></template>
