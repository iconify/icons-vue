<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo-7ywbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lo-7ywbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrows-up-down-left-right" /></template>
