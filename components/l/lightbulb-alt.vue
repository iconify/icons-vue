<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmaquobvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmaquobvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:lightbulb-alt" /></template>
