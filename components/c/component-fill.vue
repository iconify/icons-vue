<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pldlo5m_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pldlo5m_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:component-fill" /></template>
