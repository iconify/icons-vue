<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glxisr4qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="glxisr4qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:game-emoji" /></template>
