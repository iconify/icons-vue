<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3ce0b44e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3ce0b44e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:3-g-signal" /></template>
