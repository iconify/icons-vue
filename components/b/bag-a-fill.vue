<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzl4ict-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzl4ict-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:bag-a-fill" /></template>
