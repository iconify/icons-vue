<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3zwbtxdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="p3zwbtxdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bat" /></template>
