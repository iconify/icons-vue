<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by7dkpbhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="by7dkpbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:iris-scan-remix" /></template>
