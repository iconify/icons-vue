<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnx3shbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnx3shbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exclude-line" /></template>
