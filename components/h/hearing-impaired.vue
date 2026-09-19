<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn_ll_bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="hn_ll_bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:hearing-impaired" /></template>
