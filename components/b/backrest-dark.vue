<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emhy26btl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="emhy26btl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:backrest-dark" /></template>
