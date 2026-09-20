<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt3335b0v.css';
import '../../css/x/x35aq7bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt3335b0v"/><path class="x35aq7bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:car-dashboard-warning-bold" /></template>
