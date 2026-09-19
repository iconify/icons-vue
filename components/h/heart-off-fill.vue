<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8e1r5b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s8e1r5b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:heart-off-fill" /></template>
