<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peoad9soa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="peoad9soa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-lock" /></template>
