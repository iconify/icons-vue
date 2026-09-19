<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-0xj5x9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a-0xj5x9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:check-circle-2-fill" /></template>
