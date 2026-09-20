<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b137xabqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="b137xabqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:badge" /></template>
