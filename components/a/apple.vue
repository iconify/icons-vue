<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wybc3g-4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wybc3g-4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:apple" /></template>
