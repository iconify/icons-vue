<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5e6md03g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e5e6md03g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-skipforward" /></template>
