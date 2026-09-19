<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awf1i5bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="awf1i5bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:flushed" /></template>
