<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9sb41obi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="s9sb41obi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:group" /></template>
