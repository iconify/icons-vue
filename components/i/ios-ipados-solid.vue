<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1zbybb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d1zbybb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:ios-ipados-solid" /></template>
