<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w81d89beh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="w81d89beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clock-fill-12" /></template>
