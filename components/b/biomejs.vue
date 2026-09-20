<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgfp4ebof.css';
import '../../css/i/ipz-bu3ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":55.425};
const content = `<rect class="pgfp4ebof"/><path class="ipz-bu3ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:biomejs" /></template>
