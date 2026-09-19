<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li570cb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li570cb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:chevron-left-circle" /></template>
