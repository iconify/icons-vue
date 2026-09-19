<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw4c8tbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw4c8tbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:checkmark" /></template>
