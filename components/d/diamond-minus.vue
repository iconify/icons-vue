<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob0g1dvlc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob0g1dvlc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:diamond-minus" /></template>
