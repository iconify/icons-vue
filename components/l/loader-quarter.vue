<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu62q_mcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu62q_mcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:loader-quarter" /></template>
