<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pna9f5cye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pna9f5cye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:delaware" /></template>
