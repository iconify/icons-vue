<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4gnvtuxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p4gnvtuxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:controls-volumeoff" /></template>
