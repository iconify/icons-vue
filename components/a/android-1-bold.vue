<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4qhf1b5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4qhf1b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:android-1-bold" /></template>
