<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s42005nyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s42005nyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:filter-slash" /></template>
