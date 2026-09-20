<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idbul_oyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idbul_oyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bookmark-multiple" /></template>
