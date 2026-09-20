<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdr_c_a_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdr_c_a_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:clear-day-fill" /></template>
