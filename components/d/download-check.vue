<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krahz-g9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krahz-g9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:download-check" /></template>
