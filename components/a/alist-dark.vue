<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw4lhncak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xw4lhncak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:alist-dark" /></template>
