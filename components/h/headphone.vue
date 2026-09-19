<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa0n87zal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oa0n87zal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:headphone" /></template>
