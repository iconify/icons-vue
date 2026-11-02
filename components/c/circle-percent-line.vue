<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yve9znfxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yve9znfxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-percent-line" /></template>
