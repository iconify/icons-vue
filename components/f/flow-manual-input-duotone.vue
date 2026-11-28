<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh7d4-wmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zh7d4-wmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-manual-input-duotone" /></template>
