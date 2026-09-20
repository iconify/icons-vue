<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf7gmnyim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cf7gmnyim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:ear-botany" /></template>
