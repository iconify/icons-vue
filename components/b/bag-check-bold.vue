<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co9to228z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="co9to228z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-check-bold" /></template>
