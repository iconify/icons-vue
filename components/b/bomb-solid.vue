<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu5-bn8ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mu5-bn8ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:bomb-solid" /></template>
