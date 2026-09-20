<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbn1m_afc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbn1m_afc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrows-up-line" /></template>
