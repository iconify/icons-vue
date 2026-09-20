<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd5ctr80z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="xd5ctr80z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:data-type-double" /></template>
