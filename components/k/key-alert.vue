<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocjrkabfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocjrkabfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:key-alert" /></template>
