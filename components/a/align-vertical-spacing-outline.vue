<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-nz-qbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z-nz-qbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-vertical-spacing-outline" /></template>
