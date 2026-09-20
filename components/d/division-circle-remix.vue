<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgurrab7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vgurrab7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:division-circle-remix" /></template>
