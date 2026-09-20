<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouz5ddbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ouz5ddbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bell-solid" /></template>
