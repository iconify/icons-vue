<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjjfd2g-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jjjfd2g-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:crosswalk-markings-dashes" /></template>
