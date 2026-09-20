<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdx0f4b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdx0f4b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bike-line" /></template>
