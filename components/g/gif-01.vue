<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qljy_bckv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qljy_bckv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:gif-01" /></template>
