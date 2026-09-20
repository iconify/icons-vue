<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3m6362cm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u3m6362cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:check-outline" /></template>
