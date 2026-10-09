<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p29i2lbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p29i2lbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:check-48" /></template>
