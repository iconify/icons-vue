<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xota8vqjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xota8vqjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-notifications" /></template>
