<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9l2s-gon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="y9l2s-gon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:help-chat-1-solid" /></template>
