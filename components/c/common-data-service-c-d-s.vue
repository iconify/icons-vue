<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfs75p2ck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pfs75p2ck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:common-data-service-c-d-s" /></template>
