<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtn8hf62f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtn8hf62f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chart-trend-down-light" /></template>
