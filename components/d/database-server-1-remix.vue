<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_s86eyys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m_s86eyys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:database-server-1-remix" /></template>
