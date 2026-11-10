<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfr9t6j2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfr9t6j2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:fordpass" /></template>
