<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt08jibnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bt08jibnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:d" /></template>
