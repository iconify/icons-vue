<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svntjib2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="svntjib2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:award-trophy-outline" /></template>
