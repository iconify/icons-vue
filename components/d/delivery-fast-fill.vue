<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4km3zbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y4km3zbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:delivery-fast-fill" /></template>
