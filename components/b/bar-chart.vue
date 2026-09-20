<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clmtl9q-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-4};
const content = `<path class="clmtl9q-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:bar-chart" /></template>
