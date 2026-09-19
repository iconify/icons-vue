<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-fm_yoxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":384};
const content = `<path class="o-fm_yoxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-quote" /></template>
