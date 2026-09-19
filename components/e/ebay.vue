<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8tz-xkzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8tz-xkzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:ebay" /></template>
