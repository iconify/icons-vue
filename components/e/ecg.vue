<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj9jg98vx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mj9jg98vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:ecg" /></template>
