<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzdp6tnri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vzdp6tnri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:chat-bubble-square-warning-solid" /></template>
