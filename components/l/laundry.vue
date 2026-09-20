<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxstgrz9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pxstgrz9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:laundry" /></template>
