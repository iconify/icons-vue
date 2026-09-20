<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltoq1dbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltoq1dbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-open-source-filled" /></template>
