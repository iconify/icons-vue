<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zexsqu_kv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zexsqu_kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:global-off-line" /></template>
