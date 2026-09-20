<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/toh4a7b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="toh4a7b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-more-vertical-fill" /></template>
