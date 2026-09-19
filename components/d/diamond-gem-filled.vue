<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v27imyb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v27imyb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:diamond-gem-filled" /></template>
