<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lojou7_wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="lojou7_wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:glass" /></template>
