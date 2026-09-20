<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro9w7mcms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ro9w7mcms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:lost-and-found-remix" /></template>
