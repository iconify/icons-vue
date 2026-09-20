<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fss36bbna.css';
import '../../css/w/w3qyplb8m.css';
import '../../css/g/g1oxkbkoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fss36bbna"/><path class="w3qyplb8m"/><path class="g1oxkbkoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:domainmod-light" /></template>
