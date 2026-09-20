<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldh1zzbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ldh1zzbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:goodreads-light" /></template>
