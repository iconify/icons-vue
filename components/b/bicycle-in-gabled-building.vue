<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo0m-bcql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eo0m-bcql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bicycle-in-gabled-building" /></template>
