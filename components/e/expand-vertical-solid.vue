<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaxmk38pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kaxmk38pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:expand-vertical-solid" /></template>
