<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-r5g0vtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-r5g0vtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-bilibili" /></template>
