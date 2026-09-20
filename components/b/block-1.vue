<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd_jq-bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zd_jq-bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:block-1" /></template>
