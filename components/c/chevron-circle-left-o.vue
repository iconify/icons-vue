<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5eugu3ed.css';
import '../../css/v/vd_9zuben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q5eugu3ed"/><path class="vd_9zuben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:chevron-circle-left-o" /></template>
