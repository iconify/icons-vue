<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daghqi9jq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="daghqi9jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:instagram-dark" /></template>
