<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sut_hcb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sut_hcb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-left" /></template>
