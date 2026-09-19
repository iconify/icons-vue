<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zanfd_b2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zanfd_b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-share" /></template>
