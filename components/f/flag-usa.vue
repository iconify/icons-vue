<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp_djx_7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lp_djx_7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:flag-usa" /></template>
