<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbe-ueb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nbe-ueb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:female-reproductive-system-outline" /></template>
