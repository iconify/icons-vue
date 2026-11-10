<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzwvc-b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzwvc-b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cloud-check" /></template>
