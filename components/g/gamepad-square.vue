<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-wylebkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-wylebkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gamepad-square" /></template>
