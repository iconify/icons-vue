<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo93vsiye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo93vsiye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:brush-4-fill" /></template>
