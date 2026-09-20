<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7_ca8bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7_ca8bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:head-side-mask" /></template>
