<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3-nuobqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v3-nuobqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-beside-bench-on-ground" /></template>
