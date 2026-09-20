<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiufp5bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="eiufp5bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:align-right-solid" /></template>
