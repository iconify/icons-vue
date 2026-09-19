<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqugpjbox.css';
import '../../css/g/g8h-pj3bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mqugpjbox"/><path class="g8h-pj3bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:data-protection" /></template>
