<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6lnhy9hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j6lnhy9hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:claude-light" /></template>
