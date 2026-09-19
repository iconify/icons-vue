<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5-b86y2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5-b86y2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:cloud-solid" /></template>
