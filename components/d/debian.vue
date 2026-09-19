<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqjyuob2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uqjyuob2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:debian" /></template>
