<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x03a93bun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x03a93bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:home-heart" /></template>
