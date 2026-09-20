<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjxw1lbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mjxw1lbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:airbuds-charge-outline" /></template>
