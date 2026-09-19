<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcyq5-6nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jcyq5-6nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:a-cane" /></template>
