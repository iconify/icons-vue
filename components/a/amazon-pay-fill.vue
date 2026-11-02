<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfy6_4lcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfy6_4lcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:amazon-pay-fill" /></template>
