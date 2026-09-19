<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3n0d8bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v3n0d8bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cpr-outline" /></template>
