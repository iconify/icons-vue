<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oho-25_re.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oho-25_re"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bath-line" /></template>
