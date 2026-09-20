<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cte1i0tye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cte1i0tye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:female-groin" /></template>
