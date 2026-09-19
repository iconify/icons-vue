<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f85ruzeha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f85ruzeha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:home-01" /></template>
