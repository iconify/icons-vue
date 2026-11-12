<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8c-0vbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m8c-0vbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:glances-dark" /></template>
