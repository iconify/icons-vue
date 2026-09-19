<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib6jdpbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ib6jdpbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:flag-usa" /></template>
