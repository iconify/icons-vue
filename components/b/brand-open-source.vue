<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruq-cxb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruq-cxb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-open-source" /></template>
