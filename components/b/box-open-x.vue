<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlc_h_b0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlc_h_b0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:box-open-x" /></template>
