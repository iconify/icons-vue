<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytzb7tzwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ytzb7tzwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lingarr-dark" /></template>
