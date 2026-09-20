<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh5k_h5sj.css';
import '../../css/f/fw7m_cc5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh5k_h5sj"/><path class="fw7m_cc5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:abyss" /></template>
