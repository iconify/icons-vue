<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rva00qbbz.css';
import '../../css/j/jii8hcxej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path class="rva00qbbz"/><path class="jii8hcxej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:box-archive-1" /></template>
