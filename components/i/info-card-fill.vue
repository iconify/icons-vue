<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px1i3m8dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px1i3m8dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:info-card-fill" /></template>
