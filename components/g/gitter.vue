<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps-8lccpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="ps-8lccpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:gitter" /></template>
