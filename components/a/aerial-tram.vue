<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2yj-ob8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d2yj-ob8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:aerial-tram" /></template>
