<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv49c2bhl.css';
import '../../css/s/sw90srnhq.css';
import '../../css/i/iebf_nbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv49c2bhl"/><path class="sw90srnhq"/><path class="iebf_nbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:counter-2-line" /></template>
