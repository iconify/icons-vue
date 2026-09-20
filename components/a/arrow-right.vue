<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4oh6vw-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":16};
const content = `<path class="v4oh6vw-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-right" /></template>
