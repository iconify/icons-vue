<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slrdw5b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="slrdw5b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:c2x-outline" /></template>
