<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyvagkvjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyvagkvjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:layers-slash" /></template>
