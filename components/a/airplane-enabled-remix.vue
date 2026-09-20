<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-83k3ici.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i-83k3ici"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:airplane-enabled-remix" /></template>
