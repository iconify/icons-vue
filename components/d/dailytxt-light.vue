<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lee2lacrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lee2lacrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dailytxt-light" /></template>
