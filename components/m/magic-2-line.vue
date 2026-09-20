<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwam56gbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwam56gbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:magic-2-line" /></template>
