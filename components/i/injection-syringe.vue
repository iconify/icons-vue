<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn1k4o17k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn1k4o17k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:injection-syringe" /></template>
