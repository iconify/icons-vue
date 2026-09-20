<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmxc28bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="tmxc28bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:escalator-up-remix" /></template>
