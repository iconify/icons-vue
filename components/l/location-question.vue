<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa0g-um8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa0g-um8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:location-question" /></template>
