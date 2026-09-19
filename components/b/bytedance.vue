<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhibdboov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lhibdboov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:bytedance" /></template>
