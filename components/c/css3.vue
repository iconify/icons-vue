<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rugf8t3bq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rugf8t3bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:css3" /></template>
