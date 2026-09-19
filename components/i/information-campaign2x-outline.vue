<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvner4ofe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vvner4ofe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:information-campaign2x-outline" /></template>
