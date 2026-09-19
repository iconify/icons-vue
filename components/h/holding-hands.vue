<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgocg-gdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sgocg-gdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:holding-hands" /></template>
