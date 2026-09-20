<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfh4iu6hg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qfh4iu6hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:fork-knife-solid" /></template>
