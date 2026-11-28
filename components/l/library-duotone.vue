<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx9z9xbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx9z9xbhj primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:library-duotone" /></template>
