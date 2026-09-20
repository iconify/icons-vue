<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up_7tza4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up_7tza4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-trending-up-fill" /></template>
