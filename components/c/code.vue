<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2t7tqilv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s2t7tqilv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:code" /></template>
