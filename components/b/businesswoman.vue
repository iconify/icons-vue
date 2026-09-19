<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw33xtbeb.css';
import '../../css/u/uopwe8brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zw33xtbeb"/><path class="uopwe8brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:businesswoman" /></template>
