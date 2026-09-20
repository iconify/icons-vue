<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0_0sq8rl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0_0sq8rl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:glass-martini-alt-slash" /></template>
