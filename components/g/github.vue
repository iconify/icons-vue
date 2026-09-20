<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5k6jyb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5k6jyb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:github" /></template>
