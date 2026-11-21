<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2ep5t2cq.css';
import '../../css/b/btg1i0bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s2ep5t2cq"/><path class="btg1i0bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adobe-dreamweaver" /></template>
