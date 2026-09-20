<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le890tb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="le890tb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:building-office-solid" /></template>
