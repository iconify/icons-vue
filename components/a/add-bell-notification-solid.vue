<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dncqwk1ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dncqwk1ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:add-bell-notification-solid" /></template>
