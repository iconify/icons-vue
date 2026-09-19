<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y59p7np9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y59p7np9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:application-menu" /></template>
