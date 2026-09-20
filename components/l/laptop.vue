<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhnkr-b6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bhnkr-b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:laptop" /></template>
