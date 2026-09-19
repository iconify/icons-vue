<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez53olodr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ez53olodr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:kite" /></template>
