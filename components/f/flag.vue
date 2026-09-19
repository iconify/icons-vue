<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og4jt_bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="og4jt_bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:flag" /></template>
