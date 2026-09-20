<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v54shr-2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v54shr-2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:daisy" /></template>
