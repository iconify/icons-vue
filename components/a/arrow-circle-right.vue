<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm2z4abdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm2z4abdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrow-circle-right" /></template>
