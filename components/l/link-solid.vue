<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6ry8-b9g.css';
import '../../css/t/tyh81m_bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6ry8-b9g"/><path class="tyh81m_bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:link-solid" /></template>
