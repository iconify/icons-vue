<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eybug3bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eybug3bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:beef-fill" /></template>
