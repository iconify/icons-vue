<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-sah7b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-sah7b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:earbuds-check" /></template>
