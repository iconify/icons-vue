<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zic6etbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zic6etbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-90-bluetooth" /></template>
