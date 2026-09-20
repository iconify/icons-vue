<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9cnqzbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d9cnqzbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fork-and-spoon" /></template>
