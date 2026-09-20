<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7bld3bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i7bld3bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dish-cover-fill" /></template>
