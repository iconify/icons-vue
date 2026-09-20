<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isyu6z9ux.css';
import '../../css/z/zl5x12lyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="isyu6z9ux"/><path class="zl5x12lyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dynamodb-dashboard-light" /></template>
