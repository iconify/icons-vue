<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jis16yg7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jis16yg7o primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:droplet-duotone" /></template>
