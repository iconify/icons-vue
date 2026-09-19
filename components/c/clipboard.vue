<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb7y2kj_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb7y2kj_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:clipboard" /></template>
