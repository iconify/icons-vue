<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6qh3ib3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v6qh3ib3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:general-surgery" /></template>
