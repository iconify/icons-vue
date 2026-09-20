<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hey61xy0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hey61xy0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:adjustments-heart" /></template>
