<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmw2i_yzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmw2i_yzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-multiple-plus-outline" /></template>
