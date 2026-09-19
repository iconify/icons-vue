<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7x0_fbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l7x0_fbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:apps" /></template>
