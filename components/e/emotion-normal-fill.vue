<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq_fqub5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq_fqub5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:emotion-normal-fill" /></template>
