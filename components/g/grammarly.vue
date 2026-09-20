<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4xoj6q2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4xoj6q2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:grammarly" /></template>
