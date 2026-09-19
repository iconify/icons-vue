<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlur37j2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlur37j2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:copyright-filled" /></template>
