<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa-h3mbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oa-h3mbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:friendica" /></template>
