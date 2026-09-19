<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub88htbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub88htbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-left-1-duotone" /></template>
