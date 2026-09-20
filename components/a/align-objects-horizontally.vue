<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc7a14f7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lc7a14f7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:align-objects-horizontally" /></template>
