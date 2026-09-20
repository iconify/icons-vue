<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6p1hq_xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6p1hq_xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:heliumbrowser" /></template>
