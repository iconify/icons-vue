<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4oiss6dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e4oiss6dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:elysian-light" /></template>
