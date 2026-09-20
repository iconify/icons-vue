<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3fzzkb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t3fzzkb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linear" /></template>
