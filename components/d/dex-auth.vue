<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqkec9sqi.css';
import '../../css/g/gun75xfbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yqkec9sqi"/><circle class="gun75xfbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dex-auth" /></template>
