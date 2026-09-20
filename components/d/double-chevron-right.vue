<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwhfntbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nwhfntbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:double-chevron-right" /></template>
