<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qox-itb7z.css';
import '../../css/i/ijj0fga_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qox-itb7z"/><path class="ijj0fga_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:contact-20-bold" /></template>
