<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6i-ucciw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d6i-ucciw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:change-background-transparent-remix" /></template>
