<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl8nos89v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zl8nos89v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kasm-workspaces-light" /></template>
