<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx9_onrig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gx9_onrig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:like" /></template>
