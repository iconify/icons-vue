<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxgevzonk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxgevzonk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:corner-up-right-line" /></template>
