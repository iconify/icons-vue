<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qat35xbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qat35xbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:gallery-horizontal-end" /></template>
