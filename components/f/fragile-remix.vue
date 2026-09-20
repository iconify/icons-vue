<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk79iejtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="uk79iejtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:fragile-remix" /></template>
