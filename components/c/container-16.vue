<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqrtzabpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sqrtzabpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:container-16" /></template>
