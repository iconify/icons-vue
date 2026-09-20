<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vydw3bcwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vydw3bcwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:elasticsearch-light" /></template>
