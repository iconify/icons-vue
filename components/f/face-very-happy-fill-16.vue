<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxvd1fose.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bxvd1fose"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:face-very-happy-fill-16" /></template>
