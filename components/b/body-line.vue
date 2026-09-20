<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbsdqxnvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbsdqxnvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:body-line" /></template>
