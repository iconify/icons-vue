<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j492swbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j492swbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:armchair-solid" /></template>
