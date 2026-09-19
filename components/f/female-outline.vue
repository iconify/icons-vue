<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax4chebgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ax4chebgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:female-outline" /></template>
