<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9pf6sb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h9pf6sb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caret-left-20" /></template>
