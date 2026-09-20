<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jor5hct3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jor5hct3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-8-fill" /></template>
