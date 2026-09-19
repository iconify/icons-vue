<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0vude17c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0vude17c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:computer-speaker-outline" /></template>
