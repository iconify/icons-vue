<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/picx5jbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="picx5jbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-bottom-left" /></template>
