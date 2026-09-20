<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3iqqrbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p3iqqrbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:compass-rose" /></template>
