<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5vq2cbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5vq2cbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:equalizer-2-fill" /></template>
