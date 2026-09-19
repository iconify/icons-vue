<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cru6c8bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cru6c8bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:airplane-filled" /></template>
