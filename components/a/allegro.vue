<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-4c2875v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-4c2875v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:allegro" /></template>
