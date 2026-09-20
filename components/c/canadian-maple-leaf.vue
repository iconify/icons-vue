<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejor03bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ejor03bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:canadian-maple-leaf" /></template>
