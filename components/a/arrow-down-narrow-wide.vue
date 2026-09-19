<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbth5776q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbth5776q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-down-narrow-wide" /></template>
