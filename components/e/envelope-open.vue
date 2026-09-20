<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcw8lh66i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xcw8lh66i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:envelope-open" /></template>
