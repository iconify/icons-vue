<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9w93fb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p9w93fb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:compact-box-truck" /></template>
