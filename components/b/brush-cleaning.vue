<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek3m_ebxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ek3m_ebxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:brush-cleaning" /></template>
