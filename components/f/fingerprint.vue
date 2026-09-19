<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv9h8h9hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rv9h8h9hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:fingerprint" /></template>
