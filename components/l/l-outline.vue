<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-cvdpbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="p-cvdpbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:l-outline" /></template>
