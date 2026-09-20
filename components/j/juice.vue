<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw1lpcl0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lw1lpcl0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:juice" /></template>
