<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gva24ybfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gva24ybfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aliasvault" /></template>
