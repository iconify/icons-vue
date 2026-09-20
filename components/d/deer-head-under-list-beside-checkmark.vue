<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr5hwuboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nr5hwuboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:deer-head-under-list-beside-checkmark" /></template>
