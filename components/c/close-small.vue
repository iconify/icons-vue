<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp6o6tbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mp6o6tbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:close-small" /></template>
