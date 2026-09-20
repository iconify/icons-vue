<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2wjo-z3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o2wjo-z3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hexabot-dark" /></template>
