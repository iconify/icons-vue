<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk560ir9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk560ir9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:exit-run" /></template>
