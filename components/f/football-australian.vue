<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi-a9nbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi-a9nbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:football-australian" /></template>
