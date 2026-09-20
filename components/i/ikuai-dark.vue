<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsht-5zcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gsht-5zcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ikuai-dark" /></template>
