<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utvslpn-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="utvslpn-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:caret-left-circle" /></template>
