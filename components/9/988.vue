<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re-flo1hm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="re-flo1hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:988" /></template>
