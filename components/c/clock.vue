<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smp8q2bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smp8q2bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock" /></template>
