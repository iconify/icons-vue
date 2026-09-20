<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwuo_rm-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bwuo_rm-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:altcha" /></template>
