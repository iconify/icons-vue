<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/intbrob7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="intbrob7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:bookmark" /></template>
