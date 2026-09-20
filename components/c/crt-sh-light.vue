<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9kqq8b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r9kqq8b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crt-sh-light" /></template>
