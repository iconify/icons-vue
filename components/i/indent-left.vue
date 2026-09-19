<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad3ep5b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="ad3ep5b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:indent-left" /></template>
