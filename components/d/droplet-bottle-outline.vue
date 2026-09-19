<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa-jvobld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa-jvobld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:droplet-bottle-outline" /></template>
