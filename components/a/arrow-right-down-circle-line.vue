<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2lxhwhwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2lxhwhwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-right-down-circle-line" /></template>
