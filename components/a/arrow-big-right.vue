<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfdad1bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfdad1bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-big-right" /></template>
