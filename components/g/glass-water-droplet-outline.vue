<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr-p26y-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr-p26y-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:glass-water-droplet-outline" /></template>
