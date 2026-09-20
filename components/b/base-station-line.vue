<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjyr4dzhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjyr4dzhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:base-station-line" /></template>
