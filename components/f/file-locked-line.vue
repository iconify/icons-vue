<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-m-grb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-m-grb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-locked-line" /></template>
