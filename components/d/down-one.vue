<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt9uwhbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vt9uwhbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:down-one" /></template>
