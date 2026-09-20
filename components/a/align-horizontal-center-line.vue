<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v95x24b6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v95x24b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:align-horizontal-center-line" /></template>
