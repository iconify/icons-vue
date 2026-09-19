<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcw0tzvsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fcw0tzvsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:k" /></template>
