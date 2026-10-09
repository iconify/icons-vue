<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzn-fsb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vzn-fsb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caret-right-48" /></template>
