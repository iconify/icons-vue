<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka9r9wlnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ka9r9wlnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hang-up-1" /></template>
