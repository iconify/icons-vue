<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6uue9b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="h6uue9b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:bladder-outline" /></template>
