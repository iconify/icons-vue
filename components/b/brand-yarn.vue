<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i20lqzbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i20lqzbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-yarn" /></template>
