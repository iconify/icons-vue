<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq-edkbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zq-edkbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:american-express-light" /></template>
