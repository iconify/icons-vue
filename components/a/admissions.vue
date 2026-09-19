<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iywjp2bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="iywjp2bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:admissions" /></template>
