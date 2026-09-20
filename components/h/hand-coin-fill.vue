<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai7-fx85j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai7-fx85j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hand-coin-fill" /></template>
