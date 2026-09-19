<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2-3fe2ip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="t2-3fe2ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:font" /></template>
