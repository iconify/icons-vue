<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp6px_r1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp6px_r1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bank-transfer-in" /></template>
