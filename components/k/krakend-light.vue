<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4u0swhdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e4u0swhdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:krakend-light" /></template>
