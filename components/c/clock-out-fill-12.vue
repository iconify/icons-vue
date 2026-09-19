<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lirk0ib9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lirk0ib9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clock-out-fill-12" /></template>
