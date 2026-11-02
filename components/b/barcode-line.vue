<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz6pnobuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz6pnobuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:barcode-line" /></template>
