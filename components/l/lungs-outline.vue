<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrctkuz_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qrctkuz_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:lungs-outline" /></template>
