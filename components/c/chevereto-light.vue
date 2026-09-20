<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h95f-xbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h95f-xbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chevereto-light" /></template>
