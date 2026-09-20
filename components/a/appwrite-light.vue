<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucs1pdbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ucs1pdbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:appwrite-light" /></template>
