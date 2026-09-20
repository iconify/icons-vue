<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj448w2ei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj448w2ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-bolt" /></template>
