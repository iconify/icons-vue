<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4bn97f2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4bn97f2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-up-right-thick" /></template>
