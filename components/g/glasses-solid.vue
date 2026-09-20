<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zid9c5b1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zid9c5b1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:glasses-solid" /></template>
