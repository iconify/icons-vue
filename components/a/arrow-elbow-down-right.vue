<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1h05m76n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1h05m76n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-elbow-down-right" /></template>
