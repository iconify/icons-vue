<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsjjrqb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsjjrqb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cigarette-off" /></template>
