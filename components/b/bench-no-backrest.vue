<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn2rj9k1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hn2rj9k1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bench-no-backrest" /></template>
