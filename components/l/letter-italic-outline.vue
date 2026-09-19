<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9oo0hb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9oo0hb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:letter-italic-outline" /></template>
