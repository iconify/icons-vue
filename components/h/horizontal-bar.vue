<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egi_r6m4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="egi_r6m4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:horizontal-bar" /></template>
