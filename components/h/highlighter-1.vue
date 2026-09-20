<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz7ph1gyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="mz7ph1gyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:highlighter-1" /></template>
