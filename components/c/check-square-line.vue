<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjv_7_bqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjv_7_bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:check-square-line" /></template>
