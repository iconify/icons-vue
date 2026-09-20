<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j68bju_gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j68bju_gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:loandash-light" /></template>
