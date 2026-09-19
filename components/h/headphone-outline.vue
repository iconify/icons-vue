<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o40c9wbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o40c9wbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:headphone-outline" /></template>
