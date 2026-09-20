<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3-3_ub0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3-3_ub0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate-color:fitbit-logo" /></template>
