<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj5tiwb9w.css';
import '../../css/i/i_m5aoo-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj5tiwb9w"/><path class="i_m5aoo-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:exclamation-triangle" /></template>
