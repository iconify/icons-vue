<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nce_cccod.css';
import '../../css/k/khwun-byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nce_cccod"/><path class="khwun-byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:database-messaging" /></template>
