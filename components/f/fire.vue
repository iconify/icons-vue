<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/echiehj1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="echiehj1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:fire" /></template>
