<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg-_w6iru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg-_w6iru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:content-writing" /></template>
