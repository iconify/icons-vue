<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnfwjq3mb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnfwjq3mb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gamepad-round-left" /></template>
