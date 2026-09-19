<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjg93ebpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjg93ebpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-up-arrow-alt" /></template>
