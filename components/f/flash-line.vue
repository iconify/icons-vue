<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk1ybccmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk1ybccmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flash-line" /></template>
