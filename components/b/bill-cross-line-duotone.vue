<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mbfzuei-h.css';
import '../../css/t/tnf8gbb-i.css';
import '../../css/z/zvakluojt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mbfzuei-h"/><path class="tnf8gbb-i"/><path class="zvakluojt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bill-cross-line-duotone" /></template>
