<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-du2rb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q-du2rb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:grid" /></template>
