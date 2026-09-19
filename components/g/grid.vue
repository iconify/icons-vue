<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_elmvb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p_elmvb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:grid" /></template>
