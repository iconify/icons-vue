<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adu9azuga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adu9azuga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:external-link-line" /></template>
