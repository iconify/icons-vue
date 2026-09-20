<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yql2vebfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yql2vebfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adnanh-webhook-light" /></template>
