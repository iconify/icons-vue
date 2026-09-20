<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufziwbb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ufziwbb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:figma-outline" /></template>
