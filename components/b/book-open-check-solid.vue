<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfi_ynbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfi_ynbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:book-open-check-solid" /></template>
