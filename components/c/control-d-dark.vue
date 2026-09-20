<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zae9-mbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zae9-mbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:control-d-dark" /></template>
