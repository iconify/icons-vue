<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xspq7il3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xspq7il3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:h" /></template>
