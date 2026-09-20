<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m304hzeot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m304hzeot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:dharmachakra" /></template>
