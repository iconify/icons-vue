<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxf1p3ugb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gxf1p3ugb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:database-server-3-solid" /></template>
