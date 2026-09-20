<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffx7jjomr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ffx7jjomr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bus-over-bus-trap" /></template>
