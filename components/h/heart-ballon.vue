<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb4fn3bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nb4fn3bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:heart-ballon" /></template>
