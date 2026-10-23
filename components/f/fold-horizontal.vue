<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh0o9zc1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uh0o9zc1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:fold-horizontal" /></template>
