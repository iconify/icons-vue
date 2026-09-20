<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrxkk9bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrxkk9bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gasoline" /></template>
