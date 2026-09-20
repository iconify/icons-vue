<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8rewko4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8rewko4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:forward" /></template>
