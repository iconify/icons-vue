<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytm_8fbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ytm_8fbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:carport" /></template>
