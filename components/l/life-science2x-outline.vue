<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdmhswmxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hdmhswmxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:life-science2x-outline" /></template>
