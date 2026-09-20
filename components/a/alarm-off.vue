<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1p--tj3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1p--tj3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:alarm-off" /></template>
