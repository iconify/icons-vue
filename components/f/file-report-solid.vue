<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os1my55bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="os1my55bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:file-report-solid" /></template>
