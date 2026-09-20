<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5wl6both.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k5wl6both"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:label-outline" /></template>
