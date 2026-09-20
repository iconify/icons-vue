<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqz9wkbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oqz9wkbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:leaf-outline" /></template>
