<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lttya_ivm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lttya_ivm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comment-remove-outline" /></template>
