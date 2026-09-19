<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py7p6nbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="py7p6nbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:campground" /></template>
