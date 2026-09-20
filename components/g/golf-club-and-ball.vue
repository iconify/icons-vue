<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le12s8byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="le12s8byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:golf-club-and-ball" /></template>
