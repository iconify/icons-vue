<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppab5wbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppab5wbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:certificate-check" /></template>
