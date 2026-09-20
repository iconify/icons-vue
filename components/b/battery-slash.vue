<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6ztcdbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="l6ztcdbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:battery-slash" /></template>
