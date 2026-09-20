<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwnqiwbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bwnqiwbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:invention" /></template>
