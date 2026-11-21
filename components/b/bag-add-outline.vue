<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwi27ebxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iwi27ebxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bag-add-outline" /></template>
