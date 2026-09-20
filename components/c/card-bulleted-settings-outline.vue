<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf6g9sb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf6g9sb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:card-bulleted-settings-outline" /></template>
