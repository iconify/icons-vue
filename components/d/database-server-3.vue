<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6ce5bejr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f6ce5bejr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:database-server-3" /></template>
