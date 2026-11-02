<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq4sgrxgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq4sgrxgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:barcode-scan-fill" /></template>
