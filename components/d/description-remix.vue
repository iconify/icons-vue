<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw3driq-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bw3driq-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:description-remix" /></template>
