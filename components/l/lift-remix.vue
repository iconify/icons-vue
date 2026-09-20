<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6yq-nbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="m6yq-nbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:lift-remix" /></template>
