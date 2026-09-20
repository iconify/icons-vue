<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbncidbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zbncidbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:letterfeed-dark" /></template>
