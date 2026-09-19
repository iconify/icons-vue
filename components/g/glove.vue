<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afk0occja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="afk0occja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:glove" /></template>
