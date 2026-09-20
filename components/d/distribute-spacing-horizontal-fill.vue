<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi2dzkbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi2dzkbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:distribute-spacing-horizontal-fill" /></template>
