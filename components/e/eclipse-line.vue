<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqnnn52mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqnnn52mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eclipse-line" /></template>
