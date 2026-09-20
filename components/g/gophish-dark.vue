<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf179ubva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qf179ubva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gophish-dark" /></template>
