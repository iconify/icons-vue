<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8oiu4brp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8oiu4brp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-open-2-line" /></template>
