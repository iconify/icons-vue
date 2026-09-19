<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks3zr9b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ks3zr9b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:fan" /></template>
