<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unuv3bb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unuv3bb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chevrons-left-right" /></template>
