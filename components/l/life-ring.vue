<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l45a1lbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l45a1lbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:life-ring" /></template>
