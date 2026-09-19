<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu1fgqbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu1fgqbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:calendar" /></template>
