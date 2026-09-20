<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as4xm9byh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as4xm9byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:apps-2-fill" /></template>
