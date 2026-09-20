<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozh_-hb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ozh_-hb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:duckdns-light" /></template>
