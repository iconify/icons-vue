<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndhsr-0ln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ndhsr-0ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:l" /></template>
