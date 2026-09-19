<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsy7fpbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qsy7fpbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:endless" /></template>
