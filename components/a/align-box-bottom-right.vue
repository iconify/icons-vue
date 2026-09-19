<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds8jiqaxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds8jiqaxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:align-box-bottom-right" /></template>
