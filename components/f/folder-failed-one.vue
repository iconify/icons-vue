<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw1exuwiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yw1exuwiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:folder-failed-one" /></template>
