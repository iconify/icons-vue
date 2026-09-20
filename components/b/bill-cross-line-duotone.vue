<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t8z3hqtgg.css';
import '../../css/t/tnf8gbb-i.css';
import '../../css/u/uiwsg29tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t8z3hqtgg"/><path class="tnf8gbb-i"/><path class="uiwsg29tk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bill-cross-line-duotone" /></template>
