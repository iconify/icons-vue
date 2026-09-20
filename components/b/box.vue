<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vouq7mimd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vouq7mimd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:box" /></template>
