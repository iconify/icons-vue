<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s37vugjmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s37vugjmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hyperpipe-dark" /></template>
