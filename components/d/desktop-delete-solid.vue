<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_5cnfhbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q_5cnfhbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:desktop-delete-solid" /></template>
