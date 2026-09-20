<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/junoztwmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="junoztwmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:archive-box-solid" /></template>
