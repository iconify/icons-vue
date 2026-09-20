<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meb5t1aeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="meb5t1aeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:circle-9" /></template>
