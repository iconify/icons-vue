<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_exy2bih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_exy2bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bookmark-minus-solid" /></template>
