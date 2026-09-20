<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi9dnccku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi9dnccku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:check-filled" /></template>
