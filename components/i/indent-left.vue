<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7-z66pkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o7-z66pkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:indent-left" /></template>
