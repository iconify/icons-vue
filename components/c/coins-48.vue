<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqf7b7ozo.css';
import '../../css/x/xa5rde75k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wqf7b7ozo"/><path class="xa5rde75k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coins-48" /></template>
