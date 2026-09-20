<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns9--7zyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ns9--7zyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:line-arrow-right-circle-2-remix" /></template>
