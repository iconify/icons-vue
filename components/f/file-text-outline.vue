<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf5_33bau.css';
import '../../css/n/nx_lz50_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf5_33bau"/><path class="nx_lz50_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:file-text-outline" /></template>
