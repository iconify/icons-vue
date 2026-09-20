<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayia89h2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ayia89h2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:circle-4" /></template>
