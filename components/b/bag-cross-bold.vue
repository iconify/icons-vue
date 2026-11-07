<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrpl2sb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xrpl2sb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-cross-bold" /></template>
