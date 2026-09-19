<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg9fl3bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jg9fl3bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:dry-mouth-outline" /></template>
