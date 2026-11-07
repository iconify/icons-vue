<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grbzzob4o.css';
import '../../css/t/trg2kib5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grbzzob4o"/><path class="trg2kib5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-round-angle-outline" /></template>
