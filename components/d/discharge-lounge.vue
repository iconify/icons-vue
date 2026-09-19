<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihz0fsb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ihz0fsb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:discharge-lounge" /></template>
