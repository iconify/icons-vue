<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss617jbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss617jbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-help-fill-round" /></template>
