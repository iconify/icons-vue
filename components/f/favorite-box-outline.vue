<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttz056v2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttz056v2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:favorite-box-outline" /></template>
