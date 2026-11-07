<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-uqfkbjc.css';
import '../../css/y/yql3_6e3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-uqfkbjc"/><path clip-rule="evenodd" class="yql3_6e3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-4-outline" /></template>
