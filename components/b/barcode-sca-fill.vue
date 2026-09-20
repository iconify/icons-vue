<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t98sw_g9d.css';
import '../../css/q/q2gzyfm-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t98sw_g9d"/><path class="q2gzyfm-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:barcode-sca-fill" /></template>
