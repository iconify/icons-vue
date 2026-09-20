<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8cpwltgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8cpwltgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:castle-alt-1-line" /></template>
