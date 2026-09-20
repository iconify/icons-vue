<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0_pr_bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0_pr_bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:footprints" /></template>
