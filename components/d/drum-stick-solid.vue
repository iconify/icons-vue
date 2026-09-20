<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1bsd-mei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="h1bsd-mei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:drum-stick-solid" /></template>
