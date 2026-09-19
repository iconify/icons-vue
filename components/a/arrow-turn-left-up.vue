<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/non9dj5qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="non9dj5qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-left-up" /></template>
