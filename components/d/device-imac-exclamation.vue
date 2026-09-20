<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iavnjsv5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iavnjsv5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-imac-exclamation" /></template>
