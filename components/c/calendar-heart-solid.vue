<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezsh2vbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ezsh2vbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:calendar-heart-solid" /></template>
