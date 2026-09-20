<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yloeidcsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yloeidcsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:disable-protection" /></template>
