<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhpprfezv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhpprfezv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:apple-imac-2021" /></template>
