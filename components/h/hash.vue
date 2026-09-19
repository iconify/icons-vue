<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3k4e6igr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i3k4e6igr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:hash" /></template>
