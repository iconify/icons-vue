<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guzb39b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="guzb39b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:lightbulb" /></template>
