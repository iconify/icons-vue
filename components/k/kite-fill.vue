<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob7vlsf5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob7vlsf5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:kite-fill" /></template>
