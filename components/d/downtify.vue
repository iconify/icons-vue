<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czy_-bbfy.css';
import '../../css/w/w5btgvbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="czy_-bbfy"/><path class="w5btgvbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:downtify" /></template>
