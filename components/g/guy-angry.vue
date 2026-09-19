<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j641kob2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j641kob2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:guy-angry" /></template>
