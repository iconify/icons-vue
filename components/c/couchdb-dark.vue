<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuq0ab0qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uuq0ab0qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:couchdb-dark" /></template>
