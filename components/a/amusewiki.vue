<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/logf-5bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="logf-5bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:amusewiki" /></template>
