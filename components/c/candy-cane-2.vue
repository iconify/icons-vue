<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg029z55y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tg029z55y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:candy-cane-2" /></template>
