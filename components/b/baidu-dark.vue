<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5gxi1nof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v5gxi1nof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:baidu-dark" /></template>
