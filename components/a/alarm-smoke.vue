<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijv25sb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijv25sb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alarm-smoke" /></template>
