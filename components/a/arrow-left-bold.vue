<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztsoq-oxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztsoq-oxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-bold" /></template>
