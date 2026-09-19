<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs9wqcb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs9wqcb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:align-horizontal-justify-start" /></template>
