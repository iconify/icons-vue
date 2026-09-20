<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v158bablv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v158bablv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-wireless-30" /></template>
