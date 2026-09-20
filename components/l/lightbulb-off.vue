<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je_a-3baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je_a-3baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-off" /></template>
