<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfqcd2z2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfqcd2z2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eye-round" /></template>
