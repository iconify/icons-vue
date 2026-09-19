<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exslbg_5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="exslbg_5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circleyahoo" /></template>
