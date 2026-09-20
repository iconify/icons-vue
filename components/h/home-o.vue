<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivqu7ub_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ivqu7ub_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:home-o" /></template>
