<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm-5iib6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm-5iib6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-path-single-counterclockwise-solid" /></template>
