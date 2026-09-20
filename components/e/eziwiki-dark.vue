<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppk4v-xzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ppk4v-xzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:eziwiki-dark" /></template>
