<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeph4slhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xeph4slhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:gamepad-directional" /></template>
