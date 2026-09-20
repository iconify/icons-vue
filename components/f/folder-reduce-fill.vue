<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow_z9l4da.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow_z9l4da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-reduce-fill" /></template>
