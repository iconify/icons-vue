<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uifgws5er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uifgws5er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:bridge-one" /></template>
