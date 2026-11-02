<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br0onz2hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br0onz2hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-center-line" /></template>
