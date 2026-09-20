<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgne4ny2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mgne4ny2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:1" /></template>
