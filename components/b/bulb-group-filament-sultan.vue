<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqet__b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqet__b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-filament-sultan" /></template>
