<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az7m_bcgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="az7m_bcgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bepro" /></template>
