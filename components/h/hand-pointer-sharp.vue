<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2m_kp2fl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2m_kp2fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-pointer-sharp" /></template>
