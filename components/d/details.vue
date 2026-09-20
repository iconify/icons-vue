<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsm942blq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsm942blq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:details" /></template>
