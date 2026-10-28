<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1zdf_6bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1zdf_6bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:currency-bam" /></template>
