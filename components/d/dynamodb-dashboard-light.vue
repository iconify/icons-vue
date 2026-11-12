<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3k1g3byx.css';
import '../../css/z/zl5x12lyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t3k1g3byx"/><path class="zl5x12lyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dynamodb-dashboard-light" /></template>
