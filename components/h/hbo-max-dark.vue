<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0wvtc8gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o0wvtc8gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hbo-max-dark" /></template>
