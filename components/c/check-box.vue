<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b801yrcuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b801yrcuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:check-box" /></template>
