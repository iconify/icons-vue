<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbyab0bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbyab0bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:access-point-network-off" /></template>
