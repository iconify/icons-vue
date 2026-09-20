<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k__xz2kbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k__xz2kbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:at-line" /></template>
