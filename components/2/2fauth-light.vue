<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6tj6cbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s6tj6cbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:2fauth-light" /></template>
