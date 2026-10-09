<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctxfvynty.css';
import '../../css/o/oyow42bcu.css';
import '../../css/q/q4qbprqxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ctxfvynty"/><path class="oyow42bcu"/><path class="q4qbprqxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flood-defence-48-bold" /></template>
