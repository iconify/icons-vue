<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o17f7ebdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o17f7ebdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lava-lamp" /></template>
