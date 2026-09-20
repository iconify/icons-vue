<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht3kc_b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ht3kc_b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:admin" /></template>
