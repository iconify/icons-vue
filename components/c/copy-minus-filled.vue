<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xshfpkb5y.css';
import '../../css/u/uwmcnls3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xshfpkb5y"/><path class="uwmcnls3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:copy-minus-filled" /></template>
