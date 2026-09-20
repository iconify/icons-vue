<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyaxq1bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyaxq1bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:fidget-spinner-filled" /></template>
