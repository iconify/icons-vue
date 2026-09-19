<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv4337xae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rv4337xae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:allergies" /></template>
