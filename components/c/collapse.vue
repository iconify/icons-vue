<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q93tdvpzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q93tdvpzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:collapse" /></template>
