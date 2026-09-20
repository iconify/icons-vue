<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw6-7kbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gw6-7kbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ghostty-dark" /></template>
