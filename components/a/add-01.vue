<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxe2qqrqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxe2qqrqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:add-01" /></template>
