<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt6nv_bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xt6nv_bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:document-certificate-solid" /></template>
