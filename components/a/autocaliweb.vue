<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaqgtyjjh.css';
import '../../css/c/cr2fezr1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kaqgtyjjh"/><path class="cr2fezr1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:autocaliweb" /></template>
