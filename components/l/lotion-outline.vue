<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykegvkbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykegvkbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lotion-outline" /></template>
