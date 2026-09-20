<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj9gnobnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nj9gnobnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:document-certificate-remix" /></template>
