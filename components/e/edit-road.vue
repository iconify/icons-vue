<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp0m_8bdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp0m_8bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:edit-road" /></template>
