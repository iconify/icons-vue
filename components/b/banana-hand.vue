<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9tgmbbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x9tgmbbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:banana-hand" /></template>
