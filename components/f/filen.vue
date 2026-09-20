<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8-2fsnql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a8-2fsnql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filen" /></template>
