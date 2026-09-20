<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb_pa5bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb_pa5bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dew-point" /></template>
