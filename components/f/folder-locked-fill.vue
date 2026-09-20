<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj2mda0ym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj2mda0ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-locked-fill" /></template>
