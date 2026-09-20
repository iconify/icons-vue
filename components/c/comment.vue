<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4hp8l9sr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4hp8l9sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:comment" /></template>
