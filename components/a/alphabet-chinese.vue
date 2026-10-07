<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzaf98bbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzaf98bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alphabet-chinese" /></template>
