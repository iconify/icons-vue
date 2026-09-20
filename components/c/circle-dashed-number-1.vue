<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frn3o4jqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frn3o4jqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-number-1" /></template>
