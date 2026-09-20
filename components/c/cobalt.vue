<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7ml1bbhq.css';
import '../../css/k/k08isbc9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t7ml1bbhq"/><path class="k08isbc9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cobalt" /></template>
