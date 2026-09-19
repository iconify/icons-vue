<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob3812mib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ob3812mib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:4-outline" /></template>
