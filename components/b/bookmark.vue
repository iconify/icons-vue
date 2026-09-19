<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snawm_ovu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snawm_ovu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:bookmark" /></template>
