<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_ce3cchd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m_ce3cchd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hotel-bed-2-solid" /></template>
