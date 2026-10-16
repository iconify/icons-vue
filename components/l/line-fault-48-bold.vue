<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfi5rmbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vfi5rmbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:line-fault-48-bold" /></template>
