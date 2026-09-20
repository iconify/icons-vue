<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no-w18bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="no-w18bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:align-object-left-solid" /></template>
