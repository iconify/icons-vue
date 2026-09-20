<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg2tnebcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mg2tnebcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:coder" /></template>
